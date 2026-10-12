<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-khqclun.css';
import '../../css/l/lt58dk2xy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z-khqclun"/><path class="lt58dk2xy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:control-panel-20" {...props}></Icon>
