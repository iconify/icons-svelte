<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca5_w8bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca5_w8bkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:alarm-clock-off" {...props}></Icon>
