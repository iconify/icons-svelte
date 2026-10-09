<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg4uk4b1t.css';
import '../../css/j/j5r62vbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rg4uk4b1t"/><path class="j5r62vbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forward-20" {...props}></Icon>
