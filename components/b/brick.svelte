<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byvrfmb7t.css';
import '../../css/r/rw1w1gbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="byvrfmb7t"/><path class="rw1w1gbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:brick" {...props}></Icon>
