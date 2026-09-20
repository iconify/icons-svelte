<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5chkm_zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g5chkm_zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:outline-light" {...props}></Icon>
