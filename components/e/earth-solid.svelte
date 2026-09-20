<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn8mmbzrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn8mmbzrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:earth-solid" {...props}></Icon>
