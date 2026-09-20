<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4rg0ebxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a4rg0ebxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gate" {...props}></Icon>
