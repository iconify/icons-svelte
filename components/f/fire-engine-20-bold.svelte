<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1fi5_bhd.css';
import '../../css/p/p7vazbcay.css';
import '../../css/d/dgu6khf1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u1fi5_bhd"/><path class="p7vazbcay"/><path class="dgu6khf1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-engine-20-bold" {...props}></Icon>
