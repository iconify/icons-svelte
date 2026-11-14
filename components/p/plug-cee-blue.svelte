<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/pude0_byr.css';
import '../../css/w/we_dlvbnd.css';
import '../../css/q/qs2blf87w.css';
import '../../css/v/viq6kcbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pude0_byr"/><circle class="we_dlvbnd"/><circle class="qs2blf87w"/><circle class="viq6kcbcb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:plug-cee-blue" {...props}></Icon>
