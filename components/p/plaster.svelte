<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdoh43b3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="vdoh43b3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:plaster" {...props}></Icon>
