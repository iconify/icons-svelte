<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcqicacyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcqicacyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-text-rotation-up" {...props}></Icon>
