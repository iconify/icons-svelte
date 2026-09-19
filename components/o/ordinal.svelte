<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nan12mbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nan12mbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ordinal" {...props}></Icon>
