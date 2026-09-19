<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/h4fu5v_la.css';
import '../../css/l/lvhb8mgml.css';
import '../../css/e/emjm_bcem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h4fu5v_la"/><path class="lvhb8mgml"/><path class="emjm_bcem"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:graph-cured-stable" {...props}></Icon>
