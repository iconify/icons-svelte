<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izbihprcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izbihprcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bookmark-minus" {...props}></Icon>
