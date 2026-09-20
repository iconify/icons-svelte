<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvz5ev-fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvz5ev-fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rest-time-fill" {...props}></Icon>
