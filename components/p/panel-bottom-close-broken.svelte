<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cr-zrxblb.css';
import '../../css/d/d4_j1ps6w.css';
import '../../css/g/gep1q1bhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cr-zrxblb"/><path class="d4_j1ps6w"/><path class="gep1q1bhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-bottom-close-broken" {...props}></Icon>
