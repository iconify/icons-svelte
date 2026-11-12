<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuj-_3t9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fuj-_3t9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:biblioreads-light" {...props}></Icon>
