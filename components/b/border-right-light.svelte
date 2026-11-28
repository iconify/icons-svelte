<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmyql6bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rmyql6bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-right-light" {...props}></Icon>
