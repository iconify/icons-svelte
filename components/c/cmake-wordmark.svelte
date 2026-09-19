<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doblu-bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="doblu-bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:cmake-wordmark" {...props}></Icon>
