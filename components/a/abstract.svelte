<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oud7_ne2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oud7_ne2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:abstract" {...props}></Icon>
