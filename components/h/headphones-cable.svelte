<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9af41bwu.css';
import '../../css/e/eo9c1jb5g.css';
import '../../css/n/n0qwfabul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9af41bwu"/><path class="eo9c1jb5g"/><path class="n0qwfabul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:headphones-cable" {...props}></Icon>
