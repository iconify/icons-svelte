<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpa8qabrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="st0 wpa8qabrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:remove" {...props}></Icon>
