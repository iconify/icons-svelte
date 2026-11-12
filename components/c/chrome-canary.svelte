<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd6mj9e-i.css';
import '../../css/u/ublh2lbji.css';
import '../../css/p/phprfuhss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vd6mj9e-i"/><path class="ublh2lbji"/><path class="phprfuhss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chrome-canary" {...props}></Icon>
