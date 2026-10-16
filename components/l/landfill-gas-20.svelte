<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrmndgb7b.css';
import '../../css/i/i1s8vsfit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vrmndgb7b"/><path class="i1s8vsfit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:landfill-gas-20" {...props}></Icon>
