<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2re4u90q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z2re4u90q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:palette" {...props}></Icon>
