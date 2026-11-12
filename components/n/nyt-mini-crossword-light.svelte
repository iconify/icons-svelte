<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kffzjgb7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kffzjgb7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-mini-crossword-light" {...props}></Icon>
