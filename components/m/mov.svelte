<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ch6k2lb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ch6k2lb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mov" {...props}></Icon>
