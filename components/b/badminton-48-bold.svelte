<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_07ucb-p.css';
import '../../css/z/znfn-zmom.css';
import '../../css/f/f1udcubwc.css';
import '../../css/h/h28-9ombi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r_07ucb-p"/><path class="znfn-zmom"/><path class="f1udcubwc"/><path class="h28-9ombi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:badminton-48-bold" {...props}></Icon>
