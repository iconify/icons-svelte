<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa3_k1b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa3_k1b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-text-rotation-none" {...props}></Icon>
