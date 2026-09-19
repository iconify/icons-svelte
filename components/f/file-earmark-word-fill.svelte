<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-26_wjkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p-26_wjkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-earmark-word-fill" {...props}></Icon>
