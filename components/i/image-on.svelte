<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfj8gvdlk.css';
import '../../css/v/vlqkedb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfj8gvdlk"/><path class="vlqkedb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:image-on" {...props}></Icon>
