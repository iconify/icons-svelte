<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2bxt1pmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="t2bxt1pmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chevron-right" {...props}></Icon>
