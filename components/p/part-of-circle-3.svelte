<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb3s82fnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zb3s82fnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:part-of-circle-3" {...props}></Icon>
