<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dujky6bol.css';
import '../../css/o/oy3g_bbfg.css';
import '../../css/c/ckew2d3am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<g transform="translate(0 -822.52)"><rect transform="matrix(-.98339 .18149 .60192 .79856 0 0)" class="dujky6bol"/><rect transform="matrix(-.98528 .17093 -.59175 .80612 0 0)" class="oy3g_bbfg"/><path class="ckew2d3am"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:cabal" {...props}></Icon>
