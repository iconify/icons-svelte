<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrx4z5b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yrx4z5b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:arrowleftalt" {...props}></Icon>
