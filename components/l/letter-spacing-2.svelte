<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp0--ebus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp0--ebus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:letter-spacing-2" {...props}></Icon>
