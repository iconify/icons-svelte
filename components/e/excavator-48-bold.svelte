<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dswf7-2aj.css';
import '../../css/m/mzptizb4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dswf7-2aj"/><path class="mzptizb4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:excavator-48-bold" {...props}></Icon>
