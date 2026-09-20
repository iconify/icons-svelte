<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqh6yccnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqh6yccnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cookie-refresh" {...props}></Icon>
