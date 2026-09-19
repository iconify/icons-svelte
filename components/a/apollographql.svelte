<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1acwy92f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="r1acwy92f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:apollographql" {...props}></Icon>
