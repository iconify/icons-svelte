<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz3pgizbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz3pgizbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heart-square-solid" {...props}></Icon>
