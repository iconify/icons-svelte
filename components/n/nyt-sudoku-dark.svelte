<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzcqqobzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bzcqqobzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-sudoku-dark" {...props}></Icon>
