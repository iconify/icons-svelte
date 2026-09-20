<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fel89onfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fel89onfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:filmstrip-off" {...props}></Icon>
