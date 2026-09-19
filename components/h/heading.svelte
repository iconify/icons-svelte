<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cead6bcoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cead6bcoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:heading" {...props}></Icon>
