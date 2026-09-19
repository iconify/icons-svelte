<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi5deyflm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="gi5deyflm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-image" {...props}></Icon>
