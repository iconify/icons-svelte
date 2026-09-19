<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq0ibpu3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gq0ibpu3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:level-down-alt" {...props}></Icon>
