<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5_9ruszi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5_9ruszi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:progress-close" {...props}></Icon>
