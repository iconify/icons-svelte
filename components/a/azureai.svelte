<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/m/mu0x0scgz.css';
import '../../css/c/c2794gbjv.css';
import '../../css/g/g0oi4znzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path clip-rule="evenodd" class="mu0x0scgz"/><path class="c2794gbjv"/><path clip-rule="evenodd" class="g0oi4znzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:azureai" {...props}></Icon>
