<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5d1hd86f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f5d1hd86f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-circle" {...props}></Icon>
