<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc3cm42dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hc3cm42dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoji-woman-profile" {...props}></Icon>
