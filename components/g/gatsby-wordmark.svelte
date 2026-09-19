<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ialuzwbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ialuzwbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gatsby-wordmark" {...props}></Icon>
