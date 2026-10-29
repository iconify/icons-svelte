<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrr8yyb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrr8yyb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:align-right-duo" {...props}></Icon>
