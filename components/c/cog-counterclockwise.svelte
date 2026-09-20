<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe_takgho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe_takgho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cog-counterclockwise" {...props}></Icon>
