<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2znugpwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z2znugpwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-right-01" {...props}></Icon>
