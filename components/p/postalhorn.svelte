<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvbv_hdmb.css';
import '../../css/d/depymqbpz.css';
import '../../css/x/x2jhonbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xvbv_hdmb"/><path class="depymqbpz"/><path class="x2jhonbsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:postalhorn" {...props}></Icon>
