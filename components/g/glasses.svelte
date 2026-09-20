<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgw1jclaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kgw1jclaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:glasses" {...props}></Icon>
