<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m077kqbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":735};
const content = `<path class="m077kqbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:i-upper-case" {...props}></Icon>
