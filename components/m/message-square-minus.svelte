<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3d4y-b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3d4y-b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-square-minus" {...props}></Icon>
