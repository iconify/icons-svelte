<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/d/dkacq2k4x.css';
import '../../css/g/gaenu2bgb.css';
import '../../css/g/gp9mhbcvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dkacq2k4x"/><path class="gaenu2bgb"/><path class="gp9mhbcvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:airdrop" {...props}></Icon>
