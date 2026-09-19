<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubjs-yb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ubjs-yb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-military-rifle" {...props}></Icon>
