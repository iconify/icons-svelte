<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b85sq_bgw.css';
import '../../css/f/fzno83ceb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b85sq_bgw"/><path class="fzno83ceb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-heart-dislike" {...props}></Icon>
