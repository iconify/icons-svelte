<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y0vo7tb2u.css';
import '../../css/v/vy9mlrb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y0vo7tb2u"/><path class="vy9mlrb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-vertical" {...props}></Icon>
