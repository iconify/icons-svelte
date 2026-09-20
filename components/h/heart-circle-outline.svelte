<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/awfw_5bbu.css';
import '../../css/q/q4z7accis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<g class="h01tyzbfu"><path class="awfw_5bbu"/><path class="q4z7accis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:heart-circle-outline" {...props}></Icon>
