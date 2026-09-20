<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6wyyfavg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6wyyfavg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ghost-3-line" {...props}></Icon>
