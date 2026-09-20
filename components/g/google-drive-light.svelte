<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mztrb96xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mztrb96xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-drive-light" {...props}></Icon>
