<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixaw-ldqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixaw-ldqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-l-bulk-round" {...props}></Icon>
