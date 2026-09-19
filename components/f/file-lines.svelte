<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8uegvv_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="t8uegvv_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:file-lines" {...props}></Icon>
