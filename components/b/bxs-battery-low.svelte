<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtf55bc4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtf55bc4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-battery-low" {...props}></Icon>
