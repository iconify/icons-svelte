<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auo2y6bas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="auo2y6bas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:beating-heart" {...props}></Icon>
