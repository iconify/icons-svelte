<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haut6fkcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haut6fkcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-s-hexagon-solid" {...props}></Icon>
