<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_jhsfb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a_jhsfb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-diff-fill" {...props}></Icon>
