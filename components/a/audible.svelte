<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfb0shbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="vfb0shbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:audible" {...props}></Icon>
