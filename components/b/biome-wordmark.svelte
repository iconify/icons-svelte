<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt0s95b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pt0s95b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:biome-wordmark" {...props}></Icon>
