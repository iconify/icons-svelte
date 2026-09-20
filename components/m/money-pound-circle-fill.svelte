<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0ogmnb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y0ogmnb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:money-pound-circle-fill" {...props}></Icon>
