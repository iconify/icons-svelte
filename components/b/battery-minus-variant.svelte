<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw1-s7boi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw1-s7boi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-minus-variant" {...props}></Icon>
