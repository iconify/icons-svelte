<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyb0hxdvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="wyb0hxdvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:cursor-wordmark" {...props}></Icon>
