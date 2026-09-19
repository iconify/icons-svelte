<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e22g7d7ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="e22g7d7ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:comment" {...props}></Icon>
