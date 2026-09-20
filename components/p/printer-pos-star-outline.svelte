<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdhpu3bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdhpu3bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-pos-star-outline" {...props}></Icon>
