<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_nv8mbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g_nv8mbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-code-solid" {...props}></Icon>
