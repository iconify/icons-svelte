<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/v/v6fo1hbmi.css';
import '../../css/q/qv-p7ubas.css';
import '../../css/u/u-iqtibkl.css';
import '../../css/l/lsamq19hc.css';
import '../../css/w/wlrlsu9vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v6fo1hbmi"/><path class="qv-p7ubas"/><path class="u-iqtibkl"/><path class="lsamq19hc"/><path class="wlrlsu9vn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-library" {...props}></Icon>
