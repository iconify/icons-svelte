<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rttpcbboh.css';
import '../../css/j/jl229qvbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rttpcbboh"/><path class="jl229qvbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pingora-proxy-manager-light" {...props}></Icon>
