<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmdh48fah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="qmdh48fah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:astro-wordmark" {...props}></Icon>
