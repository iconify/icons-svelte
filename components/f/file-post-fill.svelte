<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eo40mmbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eo40mmbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:file-post-fill" {...props}></Icon>
