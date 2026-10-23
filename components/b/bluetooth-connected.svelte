<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l95xxsuzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l95xxsuzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bluetooth-connected" {...props}></Icon>
