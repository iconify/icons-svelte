<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh6v-h_xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sh6v-h_xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:camera-iris" {...props}></Icon>
