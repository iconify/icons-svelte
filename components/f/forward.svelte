<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3ejqvypu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j3ejqvypu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:forward" {...props}></Icon>
