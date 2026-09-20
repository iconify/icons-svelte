<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sh8bftvqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sh8bftvqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-heart" {...props}></Icon>
