<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7hbsbbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7hbsbbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:map-pin-5-line" {...props}></Icon>
