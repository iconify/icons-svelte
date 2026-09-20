<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_k29kjvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_k29kjvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mower-on" {...props}></Icon>
