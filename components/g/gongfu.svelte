<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/b/blwnmgb8p.css';
import '../../css/p/p791a-b5x.css';
import '../../css/e/ekhzbdo6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><circle class="blwnmgb8p"/><path class="p791a-b5x"/><path class="ekhzbdo6v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:gongfu" {...props}></Icon>
