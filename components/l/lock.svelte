<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doctjlc3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="doctjlc3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:lock" {...props}></Icon>
