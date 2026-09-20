<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqpk5pbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="uqpk5pbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-favorite-give-heart-reward-social-rating-media-heart-hand" {...props}></Icon>
