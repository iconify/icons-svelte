<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1h2zlbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y1h2zlbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-light" {...props}></Icon>
