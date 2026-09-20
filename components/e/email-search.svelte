<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx2_i26eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx2_i26eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:email-search" {...props}></Icon>
