<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo5pkcblg.css';
import '../../css/m/mbm3jfb1f.css';
import '../../css/n/nq5_p_bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bo5pkcblg"/><path class="mbm3jfb1f"/><path class="nq5_p_bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:power-station-alert-20" {...props}></Icon>
