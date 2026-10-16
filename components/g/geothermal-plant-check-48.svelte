<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5a2fp72m.css';
import '../../css/m/mtcc90b-l.css';
import '../../css/z/z4sj3ixdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v5a2fp72m"/><path class="mtcc90b-l"/><path class="z4sj3ixdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geothermal-plant-check-48" {...props}></Icon>
