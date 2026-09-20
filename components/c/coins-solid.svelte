<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzo-h1bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dzo-h1bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:coins-solid" {...props}></Icon>
