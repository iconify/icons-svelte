<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd25emlxv.css';
import '../../css/z/zesgwkbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="bd25emlxv"/><path class="zesgwkbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:kotlin" {...props}></Icon>
