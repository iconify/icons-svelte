<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8vx0ab6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8vx0ab6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:input" {...props}></Icon>
