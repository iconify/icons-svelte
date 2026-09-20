<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_vuxg-xv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c_vuxg-xv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-excel-solid" {...props}></Icon>
