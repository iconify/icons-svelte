<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqvr593jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hqvr593jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:grid-four-up" {...props}></Icon>
