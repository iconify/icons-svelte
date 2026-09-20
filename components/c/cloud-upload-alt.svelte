<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_1h_uu6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g_1h_uu6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cloud-upload-alt" {...props}></Icon>
