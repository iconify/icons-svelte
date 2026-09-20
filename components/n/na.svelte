<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qidzpxhqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="qidzpxhqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:na" {...props}></Icon>
