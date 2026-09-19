<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir2_d-n7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ir2_d-n7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ndz" {...props}></Icon>
