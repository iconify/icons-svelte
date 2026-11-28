<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx8r--8tv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx8r--8tv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloudy-solid" {...props}></Icon>
