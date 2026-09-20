<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myt71-beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myt71-beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:reiterate" {...props}></Icon>
