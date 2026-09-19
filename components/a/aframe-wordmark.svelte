<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9auvtbzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="o9auvtbzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:aframe-wordmark" {...props}></Icon>
