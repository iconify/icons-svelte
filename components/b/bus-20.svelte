<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4r3ojbrq.css';
import '../../css/c/ccfx0hgsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g4r3ojbrq"/><path class="ccfx0hgsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bus-20" {...props}></Icon>
