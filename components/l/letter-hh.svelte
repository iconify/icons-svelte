<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txd45qbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="txd45qbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:letter-hh" {...props}></Icon>
