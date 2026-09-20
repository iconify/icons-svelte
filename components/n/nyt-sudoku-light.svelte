<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hig_nhbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hig_nhbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-sudoku-light" {...props}></Icon>
