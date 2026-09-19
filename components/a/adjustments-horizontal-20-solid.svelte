<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lresordir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lresordir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:adjustments-horizontal-20-solid" {...props}></Icon>
