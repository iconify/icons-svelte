<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml9_geb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ml9_geb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:r" {...props}></Icon>
