<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in3i6fb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="in3i6fb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-night-904" {...props}></Icon>
