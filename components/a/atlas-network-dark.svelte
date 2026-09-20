<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev1riup_j.css';
import '../../css/h/hufvzydwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ev1riup_j"/><path class="hufvzydwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atlas-network-dark" {...props}></Icon>
