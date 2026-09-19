<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c65pc6_cx.css';
import '../../css/o/ohg47blkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c65pc6_cx"/><path class="ohg47blkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:css" {...props}></Icon>
