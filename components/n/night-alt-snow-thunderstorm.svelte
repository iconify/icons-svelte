<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh7i2l54q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="kh7i2l54q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-alt-snow-thunderstorm" {...props}></Icon>
