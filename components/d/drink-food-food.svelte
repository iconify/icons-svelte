<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5yr23bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s5yr23bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:drink-food-food" {...props}></Icon>
