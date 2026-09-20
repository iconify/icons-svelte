<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2h-g4b0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2h-g4b0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-s-circle-solid" {...props}></Icon>
