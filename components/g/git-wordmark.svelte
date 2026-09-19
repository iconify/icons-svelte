<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfe8m9-nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="sfe8m9-nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:git-wordmark" {...props}></Icon>
