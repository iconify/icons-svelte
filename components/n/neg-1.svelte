<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss2t-obao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":384};
const content = `<path class="ss2t-obao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:neg-1" {...props}></Icon>
