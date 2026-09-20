<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9u4-bcvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r9u4-bcvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:airpods" {...props}></Icon>
