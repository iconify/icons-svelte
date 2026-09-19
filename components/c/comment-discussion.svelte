<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln3zthrqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ln3zthrqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:comment-discussion" {...props}></Icon>
