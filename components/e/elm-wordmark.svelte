<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvwku7b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="rvwku7b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:elm-wordmark" {...props}></Icon>
