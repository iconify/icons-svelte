<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da-l02b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="da-l02b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:flip-vertical-01" {...props}></Icon>
