<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjx1gv_9g.css';
import '../../css/a/aavawy-uf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kjx1gv_9g"/><path class="aavawy-uf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:jar" {...props}></Icon>
