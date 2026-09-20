<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygj9995gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygj9995gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:award-trophy-1" {...props}></Icon>
