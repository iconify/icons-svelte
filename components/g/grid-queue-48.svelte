<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbo_5h3_g.css';
import '../../css/a/aohc2wbew.css';
import '../../css/h/hss_7gbmm.css';
import '../../css/w/wb3b4xbcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fbo_5h3_g"/><path class="aohc2wbew"/><path class="hss_7gbmm"/><path class="wb3b4xbcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-queue-48" {...props}></Icon>
