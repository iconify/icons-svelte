<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd91mzb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fd91mzb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:facility-groups" {...props}></Icon>
