<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw02hh1vb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nw02hh1vb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:fish-fins" {...props}></Icon>
