<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl_b26bzx.css';
import '../../css/o/oewx-qbfa.css';
import '../../css/m/mzed39b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rl_b26bzx"/><path class="oewx-qbfa"/><path class="mzed39b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fingerprint-48-bold" {...props}></Icon>
