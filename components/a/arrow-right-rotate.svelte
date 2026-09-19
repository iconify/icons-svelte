<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrbh40buu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jrbh40buu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrow-right-rotate" {...props}></Icon>
