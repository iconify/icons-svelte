<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuaejacgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuaejacgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:drafting-compass-filled" {...props}></Icon>
