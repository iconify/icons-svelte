<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn9l6bbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yn9l6bbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkwarden-dark" {...props}></Icon>
