<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbzbio0ay.css';
import '../../css/p/pbl0q7bew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gbzbio0ay"/><path class="pbl0q7bew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:palette-20-bold" {...props}></Icon>
