<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/b/bb77y_tlh.css';
import '../../css/u/uvu2kv68p.css';
import '../../css/w/wbw_ixbrw.css';
import '../../css/y/yad62e0rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="bb77y_tlh"/><path class="uvu2kv68p"/><path class="wbw_ixbrw"/><ellipse class="yad62e0rw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:expressionless-square-broken" {...props}></Icon>
