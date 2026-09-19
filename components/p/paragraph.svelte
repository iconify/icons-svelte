<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1n8pqbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="j1n8pqbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:paragraph" {...props}></Icon>
