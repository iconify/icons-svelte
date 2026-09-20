<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2c1qrbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="y2c1qrbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-night-906" {...props}></Icon>
