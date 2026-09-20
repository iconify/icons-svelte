<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gei4pxbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gei4pxbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pingvin-share-light" {...props}></Icon>
