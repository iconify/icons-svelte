<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjeb2y1lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yjeb2y1lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:android" {...props}></Icon>
