<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u25sb9b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="u25sb9b5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:lastfm" {...props}></Icon>
