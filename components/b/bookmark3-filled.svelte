<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwj9zrqlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwj9zrqlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bookmark3-filled" {...props}></Icon>
