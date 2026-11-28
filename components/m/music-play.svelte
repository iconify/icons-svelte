<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxq98cb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxq98cb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:music-play" {...props}></Icon>
