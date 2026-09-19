<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6kw9kb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="j6kw9kb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:digital1" {...props}></Icon>
