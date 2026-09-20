<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygo8ey9ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygo8ey9ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:map-target-2" {...props}></Icon>
