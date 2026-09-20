<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya-1p426h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ya-1p426h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:default-small" {...props}></Icon>
