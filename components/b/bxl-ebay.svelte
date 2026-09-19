<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu3iebblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yu3iebblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-ebay" {...props}></Icon>
