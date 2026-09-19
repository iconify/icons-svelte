<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh4riuv9c.css';
import '../../css/c/cw8brcc2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh4riuv9c"/><path class="cw8brcc2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bullseye" {...props}></Icon>
