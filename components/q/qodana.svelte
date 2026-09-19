<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvh7ehb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rvh7ehb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:qodana" {...props}></Icon>
