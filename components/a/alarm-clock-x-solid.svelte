<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmeug5b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmeug5b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:alarm-clock-x-solid" {...props}></Icon>
