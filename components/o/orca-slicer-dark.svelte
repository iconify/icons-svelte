<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blzm3ki0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="blzm3ki0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:orca-slicer-dark" {...props}></Icon>
