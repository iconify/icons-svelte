<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjzwcnbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hjzwcnbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:hump" {...props}></Icon>
