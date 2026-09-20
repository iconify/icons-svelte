<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt_-b4bfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt_-b4bfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-plus" {...props}></Icon>
