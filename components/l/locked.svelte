<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_br1i1fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k_br1i1fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:locked" {...props}></Icon>
