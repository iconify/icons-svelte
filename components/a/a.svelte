<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucb6iofxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ucb6iofxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:a" {...props}></Icon>
