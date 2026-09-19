<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0rt-zb2s.css';
import '../../css/h/hgpzimtyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s0rt-zb2s"/><path class="hgpzimtyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:chart-column-floating" {...props}></Icon>
