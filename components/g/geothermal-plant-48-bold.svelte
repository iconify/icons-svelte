<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkpyk6brm.css';
import '../../css/f/f61frvbiv.css';
import '../../css/l/lknw7jshi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rkpyk6brm"/><path class="f61frvbiv"/><path class="lknw7jshi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geothermal-plant-48-bold" {...props}></Icon>
