<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvjs-pbfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvjs-pbfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-twitter" {...props}></Icon>
