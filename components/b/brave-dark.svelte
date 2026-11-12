<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr0iznzbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wr0iznzbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:brave-dark" {...props}></Icon>
