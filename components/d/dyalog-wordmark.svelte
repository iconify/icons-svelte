<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj8ildbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tj8ildbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:dyalog-wordmark" {...props}></Icon>
