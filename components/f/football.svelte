<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/geju8gabu.css';
import '../../css/e/ehotb-rys.css';
import '../../css/z/zwy-7u4cy.css';
import '../../css/q/qp26irmvt.css';
import '../../css/m/mlirullni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="geju8gabu"/><path class="ehotb-rys"/><path class="zwy-7u4cy"/><path class="qp26irmvt"/><path class="mlirullni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:football" {...props}></Icon>
