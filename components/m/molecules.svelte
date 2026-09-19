<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/fhzkr4_3z.css';
import '../../css/n/npzbi206w.css';
import '../../css/q/qtxsezbbm.css';
import '../../css/o/o1u583b9p.css';
import '../../css/v/v2dxglbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="fhzkr4_3z"/><circle class="npzbi206w"/><circle class="qtxsezbbm"/><circle class="o1u583b9p"/><path class="v2dxglbqj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:molecules" {...props}></Icon>
