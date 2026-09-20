<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw6b3sbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="kw6b3sbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-day-313" {...props}></Icon>
