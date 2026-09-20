<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydpf4kj9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ydpf4kj9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:campsites" {...props}></Icon>
