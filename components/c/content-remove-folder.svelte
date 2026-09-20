<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvu_tubrj.css';
import '../../css/r/ry6cqhbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fvu_tubrj"/><path clip-rule="evenodd" class="ry6cqhbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-remove-folder" {...props}></Icon>
