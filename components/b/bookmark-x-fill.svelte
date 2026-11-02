<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td4k7im4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="td4k7im4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bookmark-x-fill" {...props}></Icon>
