<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st5z-kkqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="st5z-kkqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nx" {...props}></Icon>
