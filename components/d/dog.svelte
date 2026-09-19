<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj2r5rupy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nj2r5rupy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:dog" {...props}></Icon>
