<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-zwsvbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j-zwsvbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:fountain-roman-wolf" {...props}></Icon>
