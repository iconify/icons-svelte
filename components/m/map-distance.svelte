<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/i/i40tr9byn.css';
import '../../css/n/n236c5tao.css';
import '../../css/g/goy6owbsv.css';
import '../../css/g/g8rb58bfp.css';
import '../../css/l/lhui643ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="i40tr9byn"/><path class="n236c5tao"/><path class="goy6owbsv"/><path class="g8rb58bfp"/><path class="lhui643ek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:map-distance" {...props}></Icon>
