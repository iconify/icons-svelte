<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/k/kt_m-joux.css';
import '../../css/m/mh7ucwbev.css';
import '../../css/q/ql6hqqjvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="kt_m-joux"/><path class="mh7ucwbev"/><path class="ql6hqqjvi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hospital" {...props}></Icon>
