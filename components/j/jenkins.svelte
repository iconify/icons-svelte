<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r30xk0-2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="r30xk0-2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jenkins" {...props}></Icon>
