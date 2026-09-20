<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2-e3ebfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2-e3ebfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clover-outline" {...props}></Icon>
