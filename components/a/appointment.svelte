<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/c/c8rreybsc.css';
import '../../css/a/ajen750kr.css';
import '../../css/h/hek85dbhv.css';
import '../../css/t/tjuoppb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="c8rreybsc"/><path class="ajen750kr"/><circle class="hek85dbhv"/><path class="tjuoppb1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:appointment" {...props}></Icon>
