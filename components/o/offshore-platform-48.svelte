<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik1b_sbhm.css';
import '../../css/e/ecaknubvs.css';
import '../../css/o/o094g_j_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ik1b_sbhm"/><path class="ecaknubvs"/><path class="o094g_j_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offshore-platform-48" {...props}></Icon>
