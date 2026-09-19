<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7nkztb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="o7nkztb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chess-board" {...props}></Icon>
