<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll7qgv_ez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ll7qgv_ez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-export" {...props}></Icon>
