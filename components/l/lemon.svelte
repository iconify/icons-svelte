<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_u_7tbvg.css';
import '../../css/i/i71-ju5_c.css';
import '../../css/y/ytd2ngj_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n_u_7tbvg"/><path class="i71-ju5_c"/><path class="ytd2ngj_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:lemon" {...props}></Icon>
