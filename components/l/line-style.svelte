<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsujs1jxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nsujs1jxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:line-style" {...props}></Icon>
