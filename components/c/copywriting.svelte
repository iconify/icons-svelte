<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7ktw7byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="i7ktw7byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:copywriting" {...props}></Icon>
