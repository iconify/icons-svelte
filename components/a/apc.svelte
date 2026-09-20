<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_gf5r_uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f_gf5r_uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apc" {...props}></Icon>
