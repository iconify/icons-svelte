<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu87s-b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu87s-b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bus" {...props}></Icon>
