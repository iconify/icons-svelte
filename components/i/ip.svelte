<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6je0znxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6je0znxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ip" {...props}></Icon>
