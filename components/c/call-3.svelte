<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xazcc-cgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xazcc-cgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:call-3" {...props}></Icon>
