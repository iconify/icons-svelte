<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg0oqp0gx.css';
import '../../css/g/gz_xjvbwh.css';
import '../../css/k/ke47qybaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg0oqp0gx"/><path class="gz_xjvbwh"/><path class="ke47qybaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:box-minimalistic-bold" {...props}></Icon>
