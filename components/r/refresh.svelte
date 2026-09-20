<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t875gx4pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="t875gx4pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:refresh" {...props}></Icon>
