<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3i547bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3i547bbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-yahoo" {...props}></Icon>
