<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9nnls9fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l9nnls9fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-play-fill" {...props}></Icon>
