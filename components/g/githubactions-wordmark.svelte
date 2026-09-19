<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3_j-gv2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="j3_j-gv2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:githubactions-wordmark" {...props}></Icon>
