<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1z83msli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="h1z83msli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:apps" {...props}></Icon>
