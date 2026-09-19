<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0kbwcbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":644};
const content = `<path class="c0kbwcbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:alignadjust" {...props}></Icon>
