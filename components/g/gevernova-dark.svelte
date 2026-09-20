<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rig-ls45m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1545,"height":1544};
const content = `<path class="rig-ls45m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gevernova-dark" {...props}></Icon>
