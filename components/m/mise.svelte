<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i90kd3j_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="i90kd3j_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:mise" {...props}></Icon>
