<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lcs_r-tfw.css';
import '../../css/v/vx77j8bxg.css';
import '../../css/x/xupzaydsh.css';
import '../../css/v/vzdx5c9so.css';
import '../../css/r/rh-s7xmlw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="lcs_r-tfw"/><path class="vx77j8bxg"/><path class="xupzaydsh"/><path class="vzdx5c9so"/><path class="rh-s7xmlw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:bank-card-two" {...props}></Icon>
