<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jukvc5ify.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jukvc5ify"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:picker-empty" {...props}></Icon>
