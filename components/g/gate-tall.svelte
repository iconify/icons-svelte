<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-1rfhblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c-1rfhblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gate-tall" {...props}></Icon>
