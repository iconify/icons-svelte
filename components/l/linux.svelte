<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppq9iy35x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ppq9iy35x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:linux" {...props}></Icon>
