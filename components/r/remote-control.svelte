<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/b/beu9ed8lh.css';
import '../../css/k/ktbh9sb3d.css';
import '../../css/c/c29zywcqy.css';
import '../../css/e/e6pgh-soq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><rect class="beu9ed8lh"/><circle class="ktbh9sb3d"/><rect class="c29zywcqy"/><path class="e6pgh-soq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:remote-control" {...props}></Icon>
