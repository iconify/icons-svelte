<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3a8u8dbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3a8u8dbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:map-minus" {...props}></Icon>
