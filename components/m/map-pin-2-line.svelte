<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8toyb40z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8toyb40z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-2-line" {...props}></Icon>
