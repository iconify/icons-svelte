<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvs623brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvs623brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:cursor-scroll-vertical-1" {...props}></Icon>
