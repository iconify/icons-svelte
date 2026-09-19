<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc9bt0gfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pc9bt0gfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:nuget-wordmark" {...props}></Icon>
