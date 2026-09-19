<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnxdmobsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="qnxdmobsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:bubble-message-quote" {...props}></Icon>
