<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr72ycbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mr72ycbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:prescription-bottle" {...props}></Icon>
