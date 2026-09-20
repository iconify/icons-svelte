<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhlo1mbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jhlo1mbfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:picture" {...props}></Icon>
