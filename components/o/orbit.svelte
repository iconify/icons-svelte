<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/l/lxtbtmbxw.css';
import '../../css/t/tjnclna9s.css';
import '../../css/v/vbbc61k-h.css';
import '../../css/w/wc3k_ibqh.css';
import '../../css/j/jt8bh8b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="lxtbtmbxw"/><path class="tjnclna9s"/><path class="vbbc61k-h"/><path class="wc3k_ibqh"/><path class="jt8bh8b_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:orbit" {...props}></Icon>
