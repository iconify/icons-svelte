<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha6__qbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ha6__qbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:iphone" {...props}></Icon>
