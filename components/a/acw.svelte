<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxjhlkb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sxjhlkb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:acw" {...props}></Icon>
