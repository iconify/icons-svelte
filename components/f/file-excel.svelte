<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyb6fervv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="uyb6fervv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-excel" {...props}></Icon>
