<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwf5pgm1r.css';
import '../../css/d/d_be55btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uwf5pgm1r"/><path class="d_be55btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:axe-48" {...props}></Icon>
