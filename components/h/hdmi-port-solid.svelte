<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvz5j4bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yvz5j4bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hdmi-port-solid" {...props}></Icon>
