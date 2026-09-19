<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0j4x9bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n0j4x9bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:code-block" {...props}></Icon>
