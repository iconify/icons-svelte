<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb0kjw99d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":432};
const content = `<path class="fb0kjw99d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:alarm-off" {...props}></Icon>
