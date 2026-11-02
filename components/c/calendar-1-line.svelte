<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o48qy4bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o48qy4bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:calendar-1-line" {...props}></Icon>
