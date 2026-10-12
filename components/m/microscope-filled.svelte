<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl_5w4b-x.css';
import '../../css/d/dr823obko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fl_5w4b-x"/><path class="dr823obko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:microscope-filled" {...props}></Icon>
