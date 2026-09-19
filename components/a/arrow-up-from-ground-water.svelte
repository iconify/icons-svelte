<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z14k1koii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="z14k1koii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrow-up-from-ground-water" {...props}></Icon>
