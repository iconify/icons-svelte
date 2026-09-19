<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nygshlbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="nygshlbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:network-outline" {...props}></Icon>
