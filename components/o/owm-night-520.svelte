<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue86ivb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ue86ivb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-night-520" {...props}></Icon>
