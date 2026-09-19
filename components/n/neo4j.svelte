<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/ltrfubbro.css';
import '../../css/a/a7s1jvk0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="ft5dv1b6b"><path class="ltrfubbro"/><path class="a7s1jvk0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:neo4j" {...props}></Icon>
