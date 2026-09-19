<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avg_rrboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="avg_rrboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:k6" {...props}></Icon>
