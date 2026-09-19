<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/pao9cab5l.css';
import '../../css/n/nbo5_vccv.css';
import '../../css/r/rhfhlozer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pao9cab5l"/><path class="nbo5_vccv"/><path class="rhfhlozer"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:refresh-double" {...props}></Icon>
