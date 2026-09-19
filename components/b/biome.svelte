<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3av7_6pt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="q3av7_6pt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:biome" {...props}></Icon>
