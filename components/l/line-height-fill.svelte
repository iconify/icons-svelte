<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytdk_ib9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ytdk_ib9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:line-height-fill" {...props}></Icon>
