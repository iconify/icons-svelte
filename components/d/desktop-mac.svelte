<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w323g6bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":432};
const content = `<path class="w323g6bsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:desktop-mac" {...props}></Icon>
