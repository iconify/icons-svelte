<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dd8h75b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="dd8h75b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:border-none" {...props}></Icon>
