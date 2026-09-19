<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thf86pb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thf86pb_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:frame-simple" {...props}></Icon>
