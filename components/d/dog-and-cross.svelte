<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f249w635h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f249w635h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:dog-and-cross" {...props}></Icon>
