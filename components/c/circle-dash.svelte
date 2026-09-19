<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg0-lccqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rg0-lccqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:circle-dash" {...props}></Icon>
