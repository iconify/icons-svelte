<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_wpfdbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w_wpfdbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nano-wordmark" {...props}></Icon>
