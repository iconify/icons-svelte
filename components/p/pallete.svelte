<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_kfolbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l_kfolbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:pallete" {...props}></Icon>
