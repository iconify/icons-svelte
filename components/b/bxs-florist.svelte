<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv4c8bc2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iv4c8bc2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-florist" {...props}></Icon>
