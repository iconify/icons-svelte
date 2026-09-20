<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0-7x5jzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r0-7x5jzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kinopoisk" {...props}></Icon>
