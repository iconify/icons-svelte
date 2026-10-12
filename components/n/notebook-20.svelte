<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flebhl8-j.css';
import '../../css/i/ioxwpib4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="flebhl8-j"/><path class="ioxwpib4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:notebook-20" {...props}></Icon>
