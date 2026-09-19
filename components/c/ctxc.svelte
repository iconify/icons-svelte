<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef8m4s5nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ef8m4s5nf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ctxc" {...props}></Icon>
