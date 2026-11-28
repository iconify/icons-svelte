<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxhz6yb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxhz6yb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:award" {...props}></Icon>
