<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evn16v82j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evn16v82j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:queue-music" {...props}></Icon>
