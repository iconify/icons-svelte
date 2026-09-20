<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl7_itbah.css';
import '../../css/i/i8zs08y5g.css';
import '../../css/e/es2jbccom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="xl7_itbah"/><path class="i8zs08y5g"/><path class="es2jbccom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-hexagon" {...props}></Icon>
