<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwc4rkb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwc4rkb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:elastic-stack" {...props}></Icon>
