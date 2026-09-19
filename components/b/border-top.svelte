<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g65dh25ar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g65dh25ar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:border-top" {...props}></Icon>
