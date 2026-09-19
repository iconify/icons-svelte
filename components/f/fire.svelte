<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svf39sb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="svf39sb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:fire" {...props}></Icon>
