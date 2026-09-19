<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kep1zf04e.css';
import '../../css/n/na94o3ufs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="kep1zf04e"/><path class="na94o3ufs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map-user" {...props}></Icon>
