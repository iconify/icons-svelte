<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxl344bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cxl344bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:crop" {...props}></Icon>
