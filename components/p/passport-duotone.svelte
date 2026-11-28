<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a9q4f0b9w.css';
import '../../css/f/f6uir55zz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="a9q4f0b9w"/><path class="f6uir55zz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:passport-duotone" {...props}></Icon>
