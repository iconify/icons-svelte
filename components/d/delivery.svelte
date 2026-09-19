<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzab02bem.css';
import '../../css/r/rl2fx36gi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dzab02bem"/><path class="rl2fx36gi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:delivery" {...props}></Icon>
