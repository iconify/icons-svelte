<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/iauzcee-u.css';
import '../../css/c/c6gs9jbec.css';
import '../../css/n/nrljxrvxd.css';
import '../../css/x/xqz_5lfhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iauzcee-u"/><path class="c6gs9jbec"/><path class="nrljxrvxd"/><path class="xqz_5lfhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:frame-broken" {...props}></Icon>
