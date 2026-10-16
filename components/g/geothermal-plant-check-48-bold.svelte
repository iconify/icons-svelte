<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4bkgwbdg.css';
import '../../css/d/d0q_czbpk.css';
import '../../css/j/jvzo1llrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k4bkgwbdg"/><path class="d0q_czbpk"/><path class="jvzo1llrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:geothermal-plant-check-48-bold" {...props}></Icon>
