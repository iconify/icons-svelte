<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/a0tu6zjre.css';
import '../../css/d/d3p2npepl.css';
import '../../css/u/uahprbbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a0tu6zjre"/><path class="d3p2npepl"/><path class="uahprbbwf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:gymnastic" {...props}></Icon>
