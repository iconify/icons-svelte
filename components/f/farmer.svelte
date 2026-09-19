<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig8r8u_xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ig8r8u_xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:farmer" {...props}></Icon>
