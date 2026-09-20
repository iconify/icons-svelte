<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2dlt5bbm.css';
import '../../css/b/bd2_kcbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r2dlt5bbm"/><path class="bd2_kcbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:metadata-remote" {...props}></Icon>
