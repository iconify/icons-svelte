<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1y0cxqvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1y0cxqvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:paint-roller-check" {...props}></Icon>
