<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml-w7dbdb.css';
import '../../css/i/icpdw850u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="ml-w7dbdb"/><path class="icpdw850u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:driver-analysis" {...props}></Icon>
