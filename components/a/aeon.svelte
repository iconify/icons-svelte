<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl_peyboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yl_peyboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:aeon" {...props}></Icon>
