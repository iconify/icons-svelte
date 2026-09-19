<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb0dzmjui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bb0dzmjui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-customize" {...props}></Icon>
