<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4yh4hbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r4yh4hbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:minimize-window-2" {...props}></Icon>
