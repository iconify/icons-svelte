<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/divj58blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="divj58blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-g-hexagon-solid" {...props}></Icon>
