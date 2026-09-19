<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz03p4bhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="iz03p4bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:hardclipcurve" {...props}></Icon>
