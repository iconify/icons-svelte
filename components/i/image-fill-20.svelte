<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzi4bo-8z.css';
import '../../css/s/seg7ew6ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fzi4bo-8z"/><path class="seg7ew6ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:image-fill-20" {...props}></Icon>
