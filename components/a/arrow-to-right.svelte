<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8u8ch62e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8u8ch62e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:arrow-to-right" {...props}></Icon>
