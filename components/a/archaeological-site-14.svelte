<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czr71fe0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="czr71fe0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:archaeological-site-14" {...props}></Icon>
