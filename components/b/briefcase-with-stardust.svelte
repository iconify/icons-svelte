<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py0s0vbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="py0s0vbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-stardust" {...props}></Icon>
