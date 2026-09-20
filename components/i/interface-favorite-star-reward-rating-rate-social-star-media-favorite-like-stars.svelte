<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7m83e-jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="e7m83e-jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-favorite-star-reward-rating-rate-social-star-media-favorite-like-stars" {...props}></Icon>
