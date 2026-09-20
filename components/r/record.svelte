<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu8ha0bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu8ha0bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:record" {...props}></Icon>
