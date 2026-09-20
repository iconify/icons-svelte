<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgk3ygrzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgk3ygrzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-minus" {...props}></Icon>
