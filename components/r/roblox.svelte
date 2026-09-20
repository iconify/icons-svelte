<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb1eob28e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":500};
const content = `<path clip-rule="evenodd" class="hb1eob28e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:roblox" {...props}></Icon>
