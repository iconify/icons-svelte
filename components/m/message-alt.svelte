<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r14gy06lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r14gy06lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-alt" {...props}></Icon>
