<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl-esobfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pl-esobfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:algolia-wordmark" {...props}></Icon>
