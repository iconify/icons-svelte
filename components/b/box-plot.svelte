<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w62ry_euj.css';
import '../../css/h/hgpzimtyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w62ry_euj"/><path class="hgpzimtyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:box-plot" {...props}></Icon>
