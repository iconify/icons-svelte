<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de0ny6bst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="de0ny6bst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:arrowdown" {...props}></Icon>
