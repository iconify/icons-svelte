<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvgqr2t8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvgqr2t8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-1-0" {...props}></Icon>
