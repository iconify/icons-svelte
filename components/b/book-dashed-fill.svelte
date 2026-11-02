<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1-j_2mkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1-j_2mkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-dashed-fill" {...props}></Icon>
