<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0i85cboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l0i85cboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:edt-loop" {...props}></Icon>
