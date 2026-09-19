<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc5fb6b1r.css';
import '../../css/l/lix3kwe4f.css';
import '../../css/m/mmrx08g_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pc5fb6b1r"/><path class="lix3kwe4f"/><path class="mmrx08g_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:road" {...props}></Icon>
