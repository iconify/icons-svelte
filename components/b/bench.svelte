<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr-1yfb-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr-1yfb-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bench" {...props}></Icon>
