<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/jk5dtfgxh.css';
import '../../css/n/nefl88bbh.css';
import '../../css/m/ml9pot7bx.css';
import '../../css/n/nyp5msqgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="jk5dtfgxh"/><path class="nefl88bbh"/><path class="ml9pot7bx"/><path class="nyp5msqgt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:jack-duo" {...props}></Icon>
