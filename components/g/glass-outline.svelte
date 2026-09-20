<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2aoxpbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2aoxpbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:glass-outline" {...props}></Icon>
