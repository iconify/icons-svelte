<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmao-rbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dmao-rbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:list-checked" {...props}></Icon>
