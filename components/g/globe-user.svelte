<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rus7i6b6q.css';
import '../../css/n/na94o3ufs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="rus7i6b6q"/><path class="na94o3ufs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-user" {...props}></Icon>
