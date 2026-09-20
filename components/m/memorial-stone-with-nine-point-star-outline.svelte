<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqj9-4brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pqj9-4brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:memorial-stone-with-nine-point-star-outline" {...props}></Icon>
