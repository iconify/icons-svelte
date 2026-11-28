<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8jq33byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="f8jq33byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:restroom-bold" {...props}></Icon>
