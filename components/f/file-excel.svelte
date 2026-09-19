<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfg7_6b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="lfg7_6b_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:file-excel" {...props}></Icon>
