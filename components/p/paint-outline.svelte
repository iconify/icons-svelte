<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flwpjz0pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flwpjz0pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paint-outline" {...props}></Icon>
