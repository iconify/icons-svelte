<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vupa5ibcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vupa5ibcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:player-fm" {...props}></Icon>
