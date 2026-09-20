<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj2hj6ivg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yj2hj6ivg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-clock" {...props}></Icon>
