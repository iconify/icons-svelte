<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zix2v434n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zix2v434n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-brake-hold" {...props}></Icon>
