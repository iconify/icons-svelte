<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/o/o_bifoc4v.css';
import '../../css/h/hsmgu8r4l.css';
import '../../css/i/irua4ub9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><rect class="o_bifoc4v"/><ellipse class="hsmgu8r4l"/><path class="irua4ub9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:pumpkin" {...props}></Icon>
