<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tluui_b4e.css';
import '../../css/t/tl_h0kbso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tluui_b4e"/><path class="tl_h0kbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:landfill-gas-20-bold" {...props}></Icon>
