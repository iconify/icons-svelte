<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhx0_eg3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hhx0_eg3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:huginn-dark" {...props}></Icon>
