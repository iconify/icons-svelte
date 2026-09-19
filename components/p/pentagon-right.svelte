<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dbg9o4ilr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbg9o4ilr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:pentagon-right" {...props}></Icon>
