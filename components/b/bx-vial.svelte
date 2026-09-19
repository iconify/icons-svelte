<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd3i9yb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hd3i9yb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-vial" {...props}></Icon>
