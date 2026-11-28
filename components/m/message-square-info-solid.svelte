<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yh0izzb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yh0izzb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-square-info-solid" {...props}></Icon>
