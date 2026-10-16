<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dix-bwb7j.css';
import '../../css/e/enqyk-b4p.css';
import '../../css/q/qh3-d7bck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dix-bwb7j"/><path class="enqyk-b4p"/><path class="qh3-d7bck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydro-plant-check-20" {...props}></Icon>
