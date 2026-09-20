<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdz93i2eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdz93i2eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-30-bluetooth" {...props}></Icon>
