<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np74lyr1f.css';
import '../../css/o/oyd07mbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="np74lyr1f"/><path class="oyd07mbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:datasette-light" {...props}></Icon>
