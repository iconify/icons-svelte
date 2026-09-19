<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yanfh6bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="yanfh6bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:loop" {...props}></Icon>
