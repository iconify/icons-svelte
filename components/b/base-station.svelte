<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8g2chp3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8g2chp3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:base-station" {...props}></Icon>
