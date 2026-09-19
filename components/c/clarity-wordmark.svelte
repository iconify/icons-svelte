<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf7n7qbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hf7n7qbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:clarity-wordmark" {...props}></Icon>
