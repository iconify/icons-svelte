<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6d4qbcgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f6d4qbcgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:files-alt" {...props}></Icon>
