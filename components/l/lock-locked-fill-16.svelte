<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blynalbvu.css';
import '../../css/n/n0vzj_b5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<rect class="blynalbvu"/><path class="n0vzj_b5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lock-locked-fill-16" {...props}></Icon>
