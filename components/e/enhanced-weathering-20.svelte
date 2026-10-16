<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxsm3nbbt.css';
import '../../css/u/u0t0ofhbn.css';
import '../../css/e/e_v0ieb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lxsm3nbbt"/><path class="u0t0ofhbn"/><path class="e_v0ieb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:enhanced-weathering-20" {...props}></Icon>
