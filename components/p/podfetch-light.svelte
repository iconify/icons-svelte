<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij4obb7ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ij4obb7ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:podfetch-light" {...props}></Icon>
