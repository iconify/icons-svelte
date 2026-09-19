<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/e/ek7otbbmh.css';
import '../../css/d/dq-gmxanu.css';
import '../../css/p/p7ljzqyoh.css';
import '../../css/t/tqb_6nb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="ek7otbbmh"/><path class="dq-gmxanu"/><path class="p7ljzqyoh"/><circle class="tqb_6nb6c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:radar-three" {...props}></Icon>
