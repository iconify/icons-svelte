<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puwg798lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="puwg798lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:linkedin" {...props}></Icon>
