<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip8rx8bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip8rx8bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:coins-minus" {...props}></Icon>
