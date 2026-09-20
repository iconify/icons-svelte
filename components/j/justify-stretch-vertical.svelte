<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rwon19h1w.css';
import '../../css/c/cgl2m5s9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rwon19h1w"/><path vector-effect="non-scaling-stroke" class="cgl2m5s9b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:justify-stretch-vertical" {...props}></Icon>
