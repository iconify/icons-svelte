<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoj03-bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zoj03-bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-award-half-star-reward-rating-rate-social-star-media-favorite-like-stars-half" {...props}></Icon>
