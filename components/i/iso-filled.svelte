<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oji3akbpr.css';
import '../../css/y/yvg_m-b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oji3akbpr"/><path class="yvg_m-b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:iso-filled" {...props}></Icon>
