<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_yitkbdf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_yitkbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-maps-light" {...props}></Icon>
