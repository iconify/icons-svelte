<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_vg3tb-o.css';
import '../../css/w/w8xuifbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p_vg3tb-o"/><path class="w8xuifbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:bloch-sphere" {...props}></Icon>
