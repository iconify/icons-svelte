<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyfun4nwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyfun4nwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:equal-line" {...props}></Icon>
