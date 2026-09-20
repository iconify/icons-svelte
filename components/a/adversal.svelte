<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cevas8bjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cevas8bjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:adversal" {...props}></Icon>
