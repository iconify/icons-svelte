<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cj_2pto_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cj_2pto_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mortar-and-pestle-with-greek-cross" {...props}></Icon>
