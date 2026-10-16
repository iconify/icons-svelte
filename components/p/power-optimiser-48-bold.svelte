<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxl5_ibwd.css';
import '../../css/w/wx675gush.css';
import '../../css/r/r3c6dl47n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sxl5_ibwd"/><path class="wx675gush"/><path class="r3c6dl47n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-optimiser-48-bold" {...props}></Icon>
