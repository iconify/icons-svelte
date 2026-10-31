<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxty1nqgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxty1nqgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-close-round" {...props}></Icon>
