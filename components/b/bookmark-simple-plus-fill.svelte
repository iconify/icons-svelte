<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz02xqbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uz02xqbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:bookmark-simple-plus-fill" {...props}></Icon>
