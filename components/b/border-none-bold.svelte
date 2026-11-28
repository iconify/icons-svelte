<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2fmwm2av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="w2fmwm2av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-none-bold" {...props}></Icon>
