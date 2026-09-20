<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xksjs3hev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xksjs3hev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:love-letter-open" {...props}></Icon>
