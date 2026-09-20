<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3vjjyk8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j3vjjyk8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:martini-glass-and-wine-bottle" {...props}></Icon>
