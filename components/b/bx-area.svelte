<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmti31bmb.css';
import '../../css/g/g-1rbpbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmti31bmb"/><path class="g-1rbpbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-area" {...props}></Icon>
