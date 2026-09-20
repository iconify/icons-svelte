<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dera1ebbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dera1ebbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-in-out-control-point-line" {...props}></Icon>
