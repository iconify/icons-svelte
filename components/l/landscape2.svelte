<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vur7jkzgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vur7jkzgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:landscape2" {...props}></Icon>
