<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehj399b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ehj399b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:biohazard" {...props}></Icon>
