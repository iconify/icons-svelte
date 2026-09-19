<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8j-mf_mt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="z8j-mf_mt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pixijs-wordmark" {...props}></Icon>
