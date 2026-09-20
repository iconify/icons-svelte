<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwdwx0byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwdwx0byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-dashed" {...props}></Icon>
