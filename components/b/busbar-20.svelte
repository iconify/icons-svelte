<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2v9llb1t.css';
import '../../css/w/wgg1ymp4s.css';
import '../../css/b/b-8x7-7tv.css';
import '../../css/q/qv6g5_dvg.css';
import '../../css/x/x1u2ck8ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t2v9llb1t"/><path class="wgg1ymp4s"/><path class="b-8x7-7tv"/><path class="qv6g5_dvg"/><path class="x1u2ck8ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:busbar-20" {...props}></Icon>
