<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8-suub8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="h8-suub8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:plus-square" {...props}></Icon>
