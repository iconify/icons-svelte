<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x90scwbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x90scwbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:network" {...props}></Icon>
