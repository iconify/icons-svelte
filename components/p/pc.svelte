<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5vjwfb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f5vjwfb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:pc" {...props}></Icon>
