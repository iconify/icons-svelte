<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5d7bg7bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x5d7bg7bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:armor-helmet" {...props}></Icon>
