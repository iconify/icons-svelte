<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5l0-3b_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c5l0-3b_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:human" {...props}></Icon>
