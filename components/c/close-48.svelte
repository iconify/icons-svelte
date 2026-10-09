<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpcpxlb-i.css';
import '../../css/u/uspm4fblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gpcpxlb-i"/><path class="uspm4fblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:close-48" {...props}></Icon>
