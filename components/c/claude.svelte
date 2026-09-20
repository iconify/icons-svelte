<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjly2peks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjly2peks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:claude" {...props}></Icon>
