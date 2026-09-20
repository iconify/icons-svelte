<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/my6nuwbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="my6nuwbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nyt-wordle-light" {...props}></Icon>
