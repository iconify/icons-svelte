<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxvnz_b5x.css';
import '../../css/n/nt25dib9o.css';
import '../../css/h/hf3904beo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uxvnz_b5x"/><path class="nt25dib9o"/><path class="hf3904beo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:house-meter-48-bold" {...props}></Icon>
