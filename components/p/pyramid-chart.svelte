<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwhhac4gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwhhac4gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:pyramid-chart" {...props}></Icon>
