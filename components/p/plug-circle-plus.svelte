<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idwbwtb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="idwbwtb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plug-circle-plus" {...props}></Icon>
