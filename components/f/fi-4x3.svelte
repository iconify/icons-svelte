<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5vgbcb_s.css';
import '../../css/t/t_skhdcko.css';
import '../../css/p/phnpi3grn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="y5vgbcb_s"/><path class="t_skhdcko"/><path class="phnpi3grn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:fi-4x3" {...props}></Icon>
