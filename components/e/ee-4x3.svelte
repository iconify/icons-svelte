<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv-nxjz8c.css';
import '../../css/j/j-gf9ybzc.css';
import '../../css/d/d20s0p7uf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="wv-nxjz8c"/><path class="j-gf9ybzc"/><path class="d20s0p7uf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ee-4x3" {...props}></Icon>
