<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2qvqe-ii.css';
import '../../css/j/j1kdqfrps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2qvqe-ii"/><path class="j1kdqfrps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-comment-check" {...props}></Icon>
