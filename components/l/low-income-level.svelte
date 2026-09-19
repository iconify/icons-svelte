<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xw0wsrbsy.css';
import '../../css/i/idelslp3k.css';
import '../../css/h/hj0drobtd.css';
import '../../css/j/jl4-3qb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="xw0wsrbsy"/><path class="idelslp3k"/><path class="hj0drobtd"/><path clip-rule="evenodd" class="jl4-3qb9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:low-income-level" {...props}></Icon>
