<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkhkx2bsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hkhkx2bsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:beaker-compact" {...props}></Icon>
