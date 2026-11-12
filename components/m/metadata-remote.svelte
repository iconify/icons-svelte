<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2dlt5bbm.css';
import '../../css/r/ruf7_zb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2dlt5bbm"/><path class="ruf7_zb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:metadata-remote" {...props}></Icon>
