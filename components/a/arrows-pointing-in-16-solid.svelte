<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3x3y2w-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z3x3y2w-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-pointing-in-16-solid" {...props}></Icon>
