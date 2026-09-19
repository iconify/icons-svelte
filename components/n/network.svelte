<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qko81wbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="qko81wbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:network" {...props}></Icon>
