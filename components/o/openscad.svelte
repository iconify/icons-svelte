<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy8314brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":641,"height":512};
const content = `<path class="hy8314brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:openscad" {...props}></Icon>
