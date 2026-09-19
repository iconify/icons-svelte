<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_pklfbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_pklfbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:image" {...props}></Icon>
