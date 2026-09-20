<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag8rzbiiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ag8rzbiiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:figma" {...props}></Icon>
