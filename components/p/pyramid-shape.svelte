<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbj-b-sfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zbj-b-sfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pyramid-shape" {...props}></Icon>
