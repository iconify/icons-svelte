<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyqguudvt.css';
import '../../css/j/j8kj3rs0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jyqguudvt"/><path class="j8kj3rs0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:rmd" {...props}></Icon>
