<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuew-5_qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1664};
const content = `<path class="iuew-5_qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pinterest-p" {...props}></Icon>
