<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/boyb725ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="boyb725ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:divide-1" {...props}></Icon>
