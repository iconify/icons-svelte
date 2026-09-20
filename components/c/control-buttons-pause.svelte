<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh56m7awr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fh56m7awr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:control-buttons-pause" {...props}></Icon>
