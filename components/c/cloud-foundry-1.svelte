<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuf0csw1g.css';
import '../../css/y/y3x4cnbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wuf0csw1g"/><path class="y3x4cnbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cloud-foundry-1" {...props}></Icon>
