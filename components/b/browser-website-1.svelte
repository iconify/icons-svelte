<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2i_vdbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="z2i_vdbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-website-1" {...props}></Icon>
