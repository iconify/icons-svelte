<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_9nzdb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d_9nzdb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:lib" {...props}></Icon>
