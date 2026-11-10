<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ficfedu0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ficfedu0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:checkmk-wordmark" {...props}></Icon>
