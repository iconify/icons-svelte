<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hifzu6bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hifzu6bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:expo-wordmark" {...props}></Icon>
