<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjzj-xbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="mjzj-xbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:mix" {...props}></Icon>
