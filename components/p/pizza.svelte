<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8i3oywkn.css';
import '../../css/z/z21o3_b_m.css';
import '../../css/h/hto_s4t-i.css';
import '../../css/h/h_by37b5d.css';
import '../../css/r/r7k7tgbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z8i3oywkn"/><path class="z21o3_b_m"/><circle transform="rotate(-40.627 307.731 283.76)" class="hto_s4t-i"/><path class="h_by37b5d"/><path class="r7k7tgbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:pizza" {...props}></Icon>
