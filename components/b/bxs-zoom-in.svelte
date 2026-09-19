<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny_2a6iec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny_2a6iec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-zoom-in" {...props}></Icon>
