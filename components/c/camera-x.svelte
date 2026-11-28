<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1fw09i4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p1fw09i4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:camera-x" {...props}></Icon>
