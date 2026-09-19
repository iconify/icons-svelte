<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmr10_dtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="cmr10_dtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:chess-knight" {...props}></Icon>
