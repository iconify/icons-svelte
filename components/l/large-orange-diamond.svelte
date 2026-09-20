<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blbxstv4s.css';
import '../../css/y/y-zi9_bzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="blbxstv4s"/><path class="y-zi9_bzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:large-orange-diamond" {...props}></Icon>
