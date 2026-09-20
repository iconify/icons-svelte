<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxgotib5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":138.039,"height":40.145,"left":-1.136,"top":-1.136};
const content = `<path class="hxgotib5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dupont" {...props}></Icon>
