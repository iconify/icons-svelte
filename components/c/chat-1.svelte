<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6yj0kbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6yj0kbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:chat-1" {...props}></Icon>
