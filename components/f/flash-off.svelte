<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z39iucxtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="z39iucxtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:flash-off" {...props}></Icon>
