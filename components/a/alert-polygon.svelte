<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt3_vab_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":448};
const content = `<path class="kt3_vab_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:alert-polygon" {...props}></Icon>
