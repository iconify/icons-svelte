<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adxq25bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adxq25bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-check-solid" {...props}></Icon>
