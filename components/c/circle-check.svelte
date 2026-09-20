<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oem5txrch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oem5txrch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:circle-check" {...props}></Icon>
