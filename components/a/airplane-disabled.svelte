<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhrif_b8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yhrif_b8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:airplane-disabled" {...props}></Icon>
