<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeid6ab-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":667,"height":672};
const content = `<path class="zeid6ab-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:eraser" {...props}></Icon>
