<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgfyyb3cr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgfyyb3cr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pot-outline" {...props}></Icon>
