<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpfyibpoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tpfyibpoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-medical-solid" {...props}></Icon>
