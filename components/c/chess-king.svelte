<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he43ubcsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="he43ubcsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chess-king" {...props}></Icon>
