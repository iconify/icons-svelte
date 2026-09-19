<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r821r0b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r821r0b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:envelope" {...props}></Icon>
