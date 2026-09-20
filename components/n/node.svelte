<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipy4p1jwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ipy4p1jwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:node" {...props}></Icon>
