<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_pz3rxhk.css';
import '../../css/t/t25eifbbg.css';
import '../../css/h/hm4sv0btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y_pz3rxhk"/><path class="t25eifbbg"/><path class="hm4sv0btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:report-48-bold" {...props}></Icon>
