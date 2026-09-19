<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcx4prbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pcx4prbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-linkedin" {...props}></Icon>
