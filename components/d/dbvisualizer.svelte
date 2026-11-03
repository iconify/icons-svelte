<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-k0yub0q.css';
import '../../css/t/tyr-cab1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="r-k0yub0q"/><path class="tyr-cab1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:dbvisualizer" {...props}></Icon>
