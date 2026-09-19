<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ardbekbnv.css';
import '../../css/x/x7in55byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ardbekbnv"/><path class="x7in55byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:memo-pad" {...props}></Icon>
