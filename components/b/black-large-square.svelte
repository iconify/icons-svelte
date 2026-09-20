<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4w6i6b8i.css';
import '../../css/u/uyqtxdb1p.css';
import '../../css/j/j5g68mb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="y4w6i6b8i"/><path class="uyqtxdb1p"/><path class="j5g68mb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-large-square" {...props}></Icon>
