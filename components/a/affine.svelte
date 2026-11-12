<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/do2_lcsjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="do2_lcsjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:affine" {...props}></Icon>
