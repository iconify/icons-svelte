<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjhp8_bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjhp8_bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:italic-bulk-round" {...props}></Icon>
