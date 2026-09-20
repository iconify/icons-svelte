<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrqbcgw4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrqbcgw4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:24-hours-line" {...props}></Icon>
