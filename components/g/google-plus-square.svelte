<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teuv0761g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="teuv0761g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:google-plus-square" {...props}></Icon>
