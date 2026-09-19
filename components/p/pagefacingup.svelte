<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbg_emk3p.css';
import '../../css/q/qrb1vdrhq.css';
import '../../css/w/whu0plbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tbg_emk3p"/><path class="qrb1vdrhq"/><path class="whu0plbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:pagefacingup" {...props}></Icon>
