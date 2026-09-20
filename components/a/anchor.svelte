<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmwlcoaaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bmwlcoaaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:anchor" {...props}></Icon>
