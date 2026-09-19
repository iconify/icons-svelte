<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0h00kdic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="j0h00kdic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:embeddedc-wordmark" {...props}></Icon>
