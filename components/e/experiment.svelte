<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/f/fyw76ccin.css';
import '../../css/g/g6h637vus.css';
import '../../css/h/hsy00uboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="fyw76ccin"/><path class="g6h637vus"/><path class="hsy00uboi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:experiment" {...props}></Icon>
