<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6tyn2y3f.css';
import '../../css/c/cel95e31f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f6tyn2y3f"/><path class="cel95e31f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:gate" {...props}></Icon>
