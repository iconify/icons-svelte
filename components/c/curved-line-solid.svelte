<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-_a-hbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m-_a-hbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:curved-line-solid" {...props}></Icon>
