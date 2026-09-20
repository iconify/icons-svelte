<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkx980bcs.css';
import '../../css/w/wy4co49ap.css';
import '../../css/m/mpnffo9bz.css';
import '../../css/c/ccv8md5ux.css';
import '../../css/i/ijutckbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hkx980bcs"/><path class="wy4co49ap"/><path class="mpnffo9bz"/><path class="ccv8md5ux"/><path class="ijutckbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-forms-light" {...props}></Icon>
