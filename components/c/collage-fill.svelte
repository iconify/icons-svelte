<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjf7ycblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjf7ycblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:collage-fill" {...props}></Icon>
