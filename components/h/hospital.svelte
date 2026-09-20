<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz6hmub-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wz6hmub-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:hospital" {...props}></Icon>
