<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1v3b-obh.css';
import '../../css/c/cgfcjfb0i.css';
import '../../css/l/lrqfpk3ka.css';
import '../../css/p/pvf-i_bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h1v3b-obh"/><path class="cgfcjfb0i"/><path class="lrqfpk3ka"/><circle class="pvf-i_bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:blossom" {...props}></Icon>
