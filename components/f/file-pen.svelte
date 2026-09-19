<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7p-s6dcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="z7p-s6dcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-pen" {...props}></Icon>
