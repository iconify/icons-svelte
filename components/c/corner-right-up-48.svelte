<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdt97jb-t.css';
import '../../css/x/xj1iovt4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zdt97jb-t"/><path class="xj1iovt4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-right-up-48" {...props}></Icon>
