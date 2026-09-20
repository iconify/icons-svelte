<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg5ymdb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="fg5ymdb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gps-filled" {...props}></Icon>
