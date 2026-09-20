<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmd_9kbvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmd_9kbvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lock-open" {...props}></Icon>
