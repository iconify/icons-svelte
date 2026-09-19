<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb7e86lle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xb7e86lle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:emoji-happy" {...props}></Icon>
