<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w90dy4fzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="w90dy4fzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chess-queen" {...props}></Icon>
