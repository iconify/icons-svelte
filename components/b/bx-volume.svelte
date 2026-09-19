<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe89p6bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe89p6bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-volume" {...props}></Icon>
