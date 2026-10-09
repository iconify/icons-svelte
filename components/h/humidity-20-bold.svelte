<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b68k1jbxl.css';
import '../../css/d/despmrd_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b68k1jbxl"/><path class="despmrd_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:humidity-20-bold" {...props}></Icon>
