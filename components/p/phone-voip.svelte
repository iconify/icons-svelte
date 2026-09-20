<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6bt-xh4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6bt-xh4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-voip" {...props}></Icon>
