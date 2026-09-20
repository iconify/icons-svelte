<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffi58xbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ffi58xbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:browser-check-solid" {...props}></Icon>
