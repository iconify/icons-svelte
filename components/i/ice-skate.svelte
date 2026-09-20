<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq-g64b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq-g64b7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:ice-skate" {...props}></Icon>
