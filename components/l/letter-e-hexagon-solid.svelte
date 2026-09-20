<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or70u-m3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or70u-m3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-e-hexagon-solid" {...props}></Icon>
