<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-yl-m8ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="m-yl-m8ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:playground-14" {...props}></Icon>
