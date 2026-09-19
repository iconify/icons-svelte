<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/k/kvnvcfb9m.css';
import '../../css/x/xy97x4bhm.css';
import '../../css/v/v5afgebvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="kvnvcfb9m"/><path class="xy97x4bhm"/><path class="v5afgebvr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:cake-four" {...props}></Icon>
