<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2qvgqaiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f2qvgqaiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-mute" {...props}></Icon>
