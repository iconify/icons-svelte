<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykhcx6d8l.css';
import '../../css/w/ww40tqben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ykhcx6d8l"/><path class="ww40tqben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-auditing" {...props}></Icon>
