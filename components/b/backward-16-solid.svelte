<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9ghmjbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z9ghmjbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:backward-16-solid" {...props}></Icon>
