<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjyj0e8rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xjyj0e8rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:microscope" {...props}></Icon>
