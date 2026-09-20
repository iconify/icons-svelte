<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eguhn5b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eguhn5b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-front" {...props}></Icon>
