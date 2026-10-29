<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/t/tpx8s4b7z.css';
import '../../css/z/zevicpjgz.css';
import '../../css/t/to5bdybou.css';
import '../../css/k/kuknt1bgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="tpx8s4b7z wm-deco"/><path class="wm-deco zevicpjgz"/><path class="to5bdybou"/><path class="kuknt1bgw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clapperboard-blueprint" {...props}></Icon>
