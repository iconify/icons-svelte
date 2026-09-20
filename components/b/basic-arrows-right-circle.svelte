<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1ucyg85g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f1ucyg85g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:basic-arrows-right-circle" {...props}></Icon>
