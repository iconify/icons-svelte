<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8hwbvb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8hwbvb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-hibernate" {...props}></Icon>
