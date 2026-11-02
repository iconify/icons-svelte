<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te7hl6udc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te7hl6udc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-4-line" {...props}></Icon>
