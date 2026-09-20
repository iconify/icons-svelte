<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc_vz2bgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="lc_vz2bgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bookmark" {...props}></Icon>
