<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdc6qymxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tdc6qymxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-rotate-left" {...props}></Icon>
