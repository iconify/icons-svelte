<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncfo34pcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1280};
const content = `<path class="ncfo34pcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:battery-2" {...props}></Icon>
