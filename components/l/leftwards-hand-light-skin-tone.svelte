<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw5_x3b-j.css';
import '../../css/j/jzkzakb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="zw5_x3b-j"/><path class="jzkzakb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:leftwards-hand-light-skin-tone" {...props}></Icon>
