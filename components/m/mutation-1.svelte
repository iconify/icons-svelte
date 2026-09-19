<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/j2ll6ybku.css';
import '../../css/m/mxz1u7bmv.css';
import '../../css/r/rvab3vb8p.css';
import '../../css/n/n0vnjtbdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="j2ll6ybku"/><path class="mxz1u7bmv"/><path class="rvab3vb8p"/><path class="n0vnjtbdr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:mutation-1" {...props}></Icon>
