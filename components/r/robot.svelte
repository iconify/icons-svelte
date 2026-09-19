<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/n/n2u8ozbbq.css';
import '../../css/y/y-qb6bbqh.css';
import '../../css/m/mybdgyglo.css';
import '../../css/t/t1x3gbbjf.css';
import '../../css/u/uohyxirab.css';
import '../../css/c/csyqkzb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><rect class="n2u8ozbbq"/><path class="y-qb6bbqh"/><circle class="mybdgyglo"/><circle class="t1x3gbbjf"/><rect class="uohyxirab"/><path class="csyqkzb7q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:robot" {...props}></Icon>
