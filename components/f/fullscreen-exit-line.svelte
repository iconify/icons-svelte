<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhzurs3ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhzurs3ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fullscreen-exit-line" {...props}></Icon>
