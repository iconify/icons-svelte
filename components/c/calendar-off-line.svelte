<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6alyac8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6alyac8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-off-line" {...props}></Icon>
