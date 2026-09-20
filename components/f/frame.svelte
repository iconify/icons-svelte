<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crkp0tb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="crkp0tb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:frame" {...props}></Icon>
