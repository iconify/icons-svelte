<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnkz51brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="jnkz51brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-favorite-dislike-1-reward-down-thumb-hand-social-media-dislike-rating" {...props}></Icon>
