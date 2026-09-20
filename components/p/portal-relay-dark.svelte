<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtjor1x3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dtjor1x3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portal-relay-dark" {...props}></Icon>
