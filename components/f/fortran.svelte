<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puo_-obzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":473,"height":512};
const content = `<path class="puo_-obzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:fortran" {...props}></Icon>
