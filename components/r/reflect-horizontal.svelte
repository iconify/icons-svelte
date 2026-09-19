<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loyjelb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="loyjelb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:reflect-horizontal" {...props}></Icon>
