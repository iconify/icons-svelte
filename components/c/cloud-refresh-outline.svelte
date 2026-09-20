<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu736w-hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu736w-hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-refresh-outline" {...props}></Icon>
