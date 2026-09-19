<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwc4nlbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pwc4nlbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chatbubble-working" {...props}></Icon>
