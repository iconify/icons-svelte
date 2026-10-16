<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5a2fp72m.css';
import '../../css/m/mtcc90b-l.css';
import '../../css/i/ikpbwe38b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v5a2fp72m"/><path class="mtcc90b-l"/><path class="ikpbwe38b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geothermal-plant-alert-48" {...props}></Icon>
