<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yudp8lbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yudp8lbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:car-lock" {...props}></Icon>
