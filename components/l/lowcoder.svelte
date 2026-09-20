<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mft1epkfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mft1epkfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lowcoder" {...props}></Icon>
