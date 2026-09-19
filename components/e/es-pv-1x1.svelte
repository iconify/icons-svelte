<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wksup-1_p.css';
import '../../css/r/r0_9jbcny.css';
import '../../css/w/wcmprwboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wksup-1_p"/><path class="r0_9jbcny"/><path class="wcmprwboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:es-pv-1x1" {...props}></Icon>
