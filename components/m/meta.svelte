<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w24kfyb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w24kfyb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:meta" {...props}></Icon>
