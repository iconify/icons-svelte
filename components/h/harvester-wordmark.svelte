<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/siao_abdn.css';
import '../../css/h/h1bx1sgau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="siao_abdn"/><path class="h1bx1sgau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:harvester-wordmark" {...props}></Icon>
