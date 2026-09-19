<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xunq0l5hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xunq0l5hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-image-alt" {...props}></Icon>
