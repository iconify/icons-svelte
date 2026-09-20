<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbxh-3qlu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbxh-3qlu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:easyjet" {...props}></Icon>
