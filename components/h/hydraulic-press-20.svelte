<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0649ib9x.css';
import '../../css/e/e6u7bf88s.css';
import '../../css/n/nyx-ipbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l0649ib9x"/><path class="e6u7bf88s"/><path class="nyx-ipbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydraulic-press-20" {...props}></Icon>
