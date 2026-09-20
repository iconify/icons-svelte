<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zh3c16bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zh3c16bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-down-2-filled" {...props}></Icon>
