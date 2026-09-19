<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/p/pea8xwbap.css';
import '../../css/x/xx2ig22fa.css';
import '../../css/b/b6mu38bbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="pea8xwbap"/><path class="xx2ig22fa"/><circle class="b6mu38bbk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:read-book" {...props}></Icon>
