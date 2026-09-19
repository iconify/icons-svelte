<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0q5nbr5o.css';
import '../../css/e/ebeqjhxfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z0q5nbr5o"/><path class="ebeqjhxfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:image-search" {...props}></Icon>
