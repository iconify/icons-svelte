<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hki4sqbjq.css';
import '../../css/l/l5goj9tdn.css';
import '../../css/n/n-g5w935x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><circle class="hki4sqbjq"/><circle class="l5goj9tdn"/><circle class="n-g5w935x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:menu-meatball" {...props}></Icon>
