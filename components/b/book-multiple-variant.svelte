<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvqeh1brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvqeh1brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-multiple-variant" {...props}></Icon>
