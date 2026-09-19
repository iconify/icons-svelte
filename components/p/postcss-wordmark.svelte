<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssbr5cvkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ssbr5cvkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:postcss-wordmark" {...props}></Icon>
