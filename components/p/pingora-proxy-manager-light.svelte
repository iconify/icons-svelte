<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqo_rg33l.css';
import '../../css/j/jl229qvbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nqo_rg33l"/><path class="jl229qvbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pingora-proxy-manager-light" {...props}></Icon>
