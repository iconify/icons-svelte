<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6p0bjl9n.css';
import '../../css/r/rkeqi4bgn.css';
import '../../css/d/d6_tdllfl.css';
import '../../css/p/pukxm4taj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6p0bjl9n"/><path class="rkeqi4bgn"/><path class="d6_tdllfl"/><path class="pukxm4taj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-2-bold" {...props}></Icon>
