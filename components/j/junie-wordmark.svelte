<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw006larm.css';
import '../../css/f/fiyc44jpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hw006larm"/><path class="fiyc44jpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:junie-wordmark" {...props}></Icon>
