<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb7zywb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cb7zywb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-chatbubble" {...props}></Icon>
