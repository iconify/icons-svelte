<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha04nrbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ha04nrbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microphone-plus" {...props}></Icon>
