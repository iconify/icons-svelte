<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ieqwf_b3i.css';
import '../../css/t/t6qum7bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ieqwf_b3i"/><path class="t6qum7bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-drive-dark" {...props}></Icon>
