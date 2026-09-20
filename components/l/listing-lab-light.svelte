<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-keuv35e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d-keuv35e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:listing-lab-light" {...props}></Icon>
