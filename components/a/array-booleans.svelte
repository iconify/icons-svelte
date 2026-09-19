<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfdmkubzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rfdmkubzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:array-booleans" {...props}></Icon>
