<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/q/qsij3zb9w.css';
import '../../css/q/qyze_cc1g.css';
import '../../css/q/qs5g--bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qsij3zb9w"/><path class="qyze_cc1g"/><path class="qs5g--bge"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:healthcare" {...props}></Icon>
