<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce6ljt2_d.css';
import '../../css/g/gpwzcjb5p.css';
import '../../css/d/d9livjodx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ce6ljt2_d"/><path class="gpwzcjb5p"/><path class="d9livjodx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-pump-ground-48-bold" {...props}></Icon>
