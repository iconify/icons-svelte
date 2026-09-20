<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-nudybhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="x-nudybhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:move-left" {...props}></Icon>
