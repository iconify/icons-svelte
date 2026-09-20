<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtv5yrb6k.css';
import '../../css/s/stxf-nbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="rtv5yrb6k"/><path class="stxf-nbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:dashboard" {...props}></Icon>
