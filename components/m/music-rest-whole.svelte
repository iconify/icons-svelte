<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxb7qbbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxb7qbbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-rest-whole" {...props}></Icon>
