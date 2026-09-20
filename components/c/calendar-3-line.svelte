<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anv1cbbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anv1cbbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-3-line" {...props}></Icon>
