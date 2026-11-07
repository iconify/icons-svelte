<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3dnrk_0v.css';
import '../../css/s/sdp_xxbiy.css';
import '../../css/t/t2or4horf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3dnrk_0v"/><path class="sdp_xxbiy"/><path class="t2or4horf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-keyhole-minimalistic-bold-duotone" {...props}></Icon>
