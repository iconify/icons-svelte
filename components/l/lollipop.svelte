<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etlc3l98h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etlc3l98h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:lollipop" {...props}></Icon>
