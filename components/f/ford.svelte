<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwm3tpbpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwm3tpbpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ford" {...props}></Icon>
