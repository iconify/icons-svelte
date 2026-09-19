<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/b/bdeot9bnh.css';
import '../../css/t/tlktmtbnx.css';
import '../../css/p/plf46m9uf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="bdeot9bnh"/><path class="tlktmtbnx"/><circle class="plf46m9uf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:assembly-line" {...props}></Icon>
