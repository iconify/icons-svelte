<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4-vqrbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="g4-vqrbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:akka-wordmark" {...props}></Icon>
