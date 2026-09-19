<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8kuy_ape.css';
import '../../css/z/z0z1a0aie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="c8kuy_ape"/><path class="z0z1a0aie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:instance-cx" {...props}></Icon>
