<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y71q3cb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="y71q3cb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:postcard-bold" {...props}></Icon>
