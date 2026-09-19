<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzxetnbiv.css';
import '../../css/x/xdjatpcmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gzxetnbiv"/><path class="xdjatpcmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:intersect" {...props}></Icon>
