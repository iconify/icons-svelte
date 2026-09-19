<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt6ij0b3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt6ij0b3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:pointer" {...props}></Icon>
