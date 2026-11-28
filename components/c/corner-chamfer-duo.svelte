<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1yyhcx7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1yyhcx7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:corner-chamfer-duo" {...props}></Icon>
