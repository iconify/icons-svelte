<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvnqahb0g.css';
import '../../css/b/b5mpx9hjg.css';
import '../../css/i/in3igcb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="rvnqahb0g"><path class="b5mpx9hjg"/><path class="in3igcb8w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:mail-send" {...props}></Icon>
