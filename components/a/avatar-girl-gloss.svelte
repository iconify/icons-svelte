<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlh6alb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k xlh6alb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-girl-gloss" {...props}></Icon>
