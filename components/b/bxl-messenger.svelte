<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krk_5tb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krk_5tb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-messenger" {...props}></Icon>
