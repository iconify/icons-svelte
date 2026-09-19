<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-9o0_b7b.css';
import '../../css/k/ka84qdbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="d-9o0_b7b"/><path class="ka84qdbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:keras" {...props}></Icon>
