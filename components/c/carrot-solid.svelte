<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5yh2cbhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w5yh2cbhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:carrot-solid" {...props}></Icon>
