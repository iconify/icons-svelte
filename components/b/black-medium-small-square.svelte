<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr2d8z97p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yr2d8z97p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:black-medium-small-square" {...props}></Icon>
