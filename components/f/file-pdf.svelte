<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phrv23brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="phrv23brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-pdf" {...props}></Icon>
