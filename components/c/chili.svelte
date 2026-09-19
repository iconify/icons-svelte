<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/w/wfnpsobxi.css';
import '../../css/d/d_q9ekb2u.css';
import '../../css/i/im3frobym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="wfnpsobxi"/><path class="d_q9ekb2u"/><path class="im3frobym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:chili" {...props}></Icon>
