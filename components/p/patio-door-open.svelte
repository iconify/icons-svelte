<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnl50ebfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnl50ebfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:patio-door-open" {...props}></Icon>
