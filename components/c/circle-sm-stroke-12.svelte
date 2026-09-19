<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjwek1blh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="hjwek1blh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-sm-stroke-12" {...props}></Icon>
