<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hctegda8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hctegda8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:desktop-tower-check" {...props}></Icon>
