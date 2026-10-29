<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty1ybmbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ty1ybmbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:juce-wordmark" {...props}></Icon>
