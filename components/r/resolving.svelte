<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu_kr_k0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="uu_kr_k0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:resolving" {...props}></Icon>
