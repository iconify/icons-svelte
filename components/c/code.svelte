<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5v5hbcke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t5v5hbcke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:code" {...props}></Icon>
