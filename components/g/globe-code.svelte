<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmdt1p3iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmdt1p3iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:globe-code" {...props}></Icon>
