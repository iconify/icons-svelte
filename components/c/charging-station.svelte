<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1lijt-zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j1lijt-zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:charging-station" {...props}></Icon>
