<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/yylgmr2nv.css';
import '../../css/c/c9obvju-w.css';
import '../../css/r/r4dmb4bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="yylgmr2nv"/><path class="c9obvju-w"/><path class="r4dmb4bvu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:covid19-virus-warning-1" {...props}></Icon>
