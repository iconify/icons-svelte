<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2w618bkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="t2w618bkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:indent" {...props}></Icon>
