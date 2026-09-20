<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqs7bev6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mqs7bev6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkding-dark" {...props}></Icon>
