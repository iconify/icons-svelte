<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqcu16-ig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="cqcu16-ig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:readthedocs-wordmark" {...props}></Icon>
