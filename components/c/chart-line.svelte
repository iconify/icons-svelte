<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3fgswk6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q3fgswk6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chart-line" {...props}></Icon>
