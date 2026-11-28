<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jo_x69yli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jo_x69yli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cast" {...props}></Icon>
