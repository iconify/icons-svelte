<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy1oo49dt.css';
import '../../css/e/e15sxdbol.css';
import '../../css/r/r5r8zsb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oy1oo49dt"/><path class="e15sxdbol"/><path class="r5r8zsb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:office-48" {...props}></Icon>
