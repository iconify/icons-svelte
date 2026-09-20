<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz401zx2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wz401zx2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alaska-airlines" {...props}></Icon>
