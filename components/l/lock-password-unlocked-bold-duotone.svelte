<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3dnrk_0v.css';
import '../../css/b/b6kz81jcw.css';
import '../../css/l/lt_dvue1n.css';
import '../../css/w/wuug2ccjk.css';
import '../../css/s/sl_boeb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3dnrk_0v"/><path class="b6kz81jcw"/><path class="lt_dvue1n"/><path class="wuug2ccjk"/><path class="sl_boeb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-password-unlocked-bold-duotone" {...props}></Icon>
