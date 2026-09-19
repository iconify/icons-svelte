<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o93lq-byo.css';
import '../../css/b/b-396ydgx.css';
import '../../css/o/oa8odlbac.css';
import '../../css/t/tqvdlybjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><circle class="b-396ydgx"/><path class="oa8odlbac"/><path class="tqvdlybjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:mirror-one" {...props}></Icon>
