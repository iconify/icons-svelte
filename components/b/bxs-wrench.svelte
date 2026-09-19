<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2tht3b8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2tht3b8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-wrench" {...props}></Icon>
