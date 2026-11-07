<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k66tt2kvs.css';
import '../../css/c/c25lkgbgb.css';
import '../../css/c/ca5b8gbur.css';
import '../../css/k/kvdjm4bsr.css';
import '../../css/r/rwnv8qbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k66tt2kvs"/><path class="c25lkgbgb"/><path class="ca5b8gbur"/><path class="kvdjm4bsr"/><path class="rwnv8qbti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:case-round-minimalistic-linear" {...props}></Icon>
