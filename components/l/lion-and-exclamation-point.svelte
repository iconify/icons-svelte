<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q71v1jb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q71v1jb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lion-and-exclamation-point" {...props}></Icon>
