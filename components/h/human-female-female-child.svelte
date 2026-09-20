<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp5oh5bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp5oh5bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:human-female-female-child" {...props}></Icon>
