<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z58sv258w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="z58sv258w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:eject" {...props}></Icon>
