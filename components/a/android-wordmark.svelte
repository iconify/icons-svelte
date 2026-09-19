<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdngab7on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rdngab7on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:android-wordmark" {...props}></Icon>
