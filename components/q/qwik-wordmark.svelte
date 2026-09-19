<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhmruibkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bhmruibkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:qwik-wordmark" {...props}></Icon>
