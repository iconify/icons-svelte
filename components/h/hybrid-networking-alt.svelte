<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8406y-qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f8406y-qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hybrid-networking-alt" {...props}></Icon>
