<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d28192bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d28192bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-right-square" {...props}></Icon>
