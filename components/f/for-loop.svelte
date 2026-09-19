<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o52mxibjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o52mxibjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:for-loop" {...props}></Icon>
