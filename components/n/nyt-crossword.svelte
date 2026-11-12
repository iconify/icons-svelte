<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6gcwac9u.css';
import '../../css/c/czq6lnb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o6gcwac9u"/><path class="czq6lnb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-crossword" {...props}></Icon>
