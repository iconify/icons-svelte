<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg-e66htg.css';
import '../../css/a/abmkmib2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dg-e66htg"/><path class="abmkmib2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nozzle-48" {...props}></Icon>
