<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea24ebbtv.css';
import '../../css/i/il3gm6b7g.css';
import '../../css/c/cvwrb4bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGI8KubeUZ" x1="256.076" x2="256.076" y1="-96.007" y2="626.727" gradientUnits="userSpaceOnUse"><stop offset="0" class="ea24ebbtv"/><stop offset="1" class="il3gm6b7g"/></linearGradient><path fill="url(#SVGI8KubeUZ)" class="cvwrb4bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:motioneye" {...props}></Icon>
