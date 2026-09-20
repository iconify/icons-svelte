<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2ys-0kzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="p2ys-0kzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:food" {...props}></Icon>
