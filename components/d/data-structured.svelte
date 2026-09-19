<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd4ogl5wu.css';
import '../../css/g/geq_pu3ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="qd4ogl5wu"/><path class="geq_pu3ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-structured" {...props}></Icon>
