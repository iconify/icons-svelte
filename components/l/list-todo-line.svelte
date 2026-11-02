<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9oz_-bvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9oz_-bvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-todo-line" {...props}></Icon>
