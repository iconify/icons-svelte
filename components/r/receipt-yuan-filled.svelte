<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8cjv2wev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8cjv2wev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:receipt-yuan-filled" {...props}></Icon>
